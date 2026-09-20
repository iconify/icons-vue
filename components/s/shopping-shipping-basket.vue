<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8e86bczb.css';
import '../../css/l/lbjnpubsy.css';
import '../../css/y/yl21lvbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q8e86bczb"/><path class="lbjnpubsy"/><path class="yl21lvbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:shopping-shipping-basket" /></template>
