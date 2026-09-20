<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uig_arbat.css';
import '../../css/p/p-744obuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uig_arbat"/><path class="p-744obuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:setting-line-duotone-line" /></template>
