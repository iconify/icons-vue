<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhk_xi9ht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mhk_xi9ht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:sleep" /></template>
