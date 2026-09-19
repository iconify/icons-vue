<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho5eq6b4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="ho5eq6b4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ei:sc-skype" /></template>
