<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncrdy1llp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ncrdy1llp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shield-minus-sharp-fill" /></template>
