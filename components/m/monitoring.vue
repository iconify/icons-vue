<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcasx0bxr.css';
import '../../css/n/n980ub85d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcasx0bxr"/><path class="n980ub85d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:monitoring" /></template>
