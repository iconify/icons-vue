<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc8rkpbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kc8rkpbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:user-sync-online-in-person-solid" /></template>
