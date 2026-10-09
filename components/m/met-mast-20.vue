<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wn4zoubux.css';
import '../../css/w/wlwzuyb0k.css';
import '../../css/r/rv76zfbuo.css';
import '../../css/f/fzro0d78h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wn4zoubux"/><path class="wlwzuyb0k"/><path class="rv76zfbuo"/><path class="fzro0d78h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:met-mast-20" /></template>
