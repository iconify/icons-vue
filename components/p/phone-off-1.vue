<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k53f7pjls.css';
import '../../css/l/l614akbje.css';
import '../../css/v/vkj_ftrwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k53f7pjls"/><path class="l614akbje"/><path class="vkj_ftrwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:phone-off-1" /></template>
