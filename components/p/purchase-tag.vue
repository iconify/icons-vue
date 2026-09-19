<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw9kcbb2m.css';
import '../../css/z/zn5t45b4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw9kcbb2m"/><circle class="zn5t45b4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:purchase-tag" /></template>
