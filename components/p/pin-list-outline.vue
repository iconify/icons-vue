<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m76_9tmlz.css';
import '../../css/f/fi7kcnkgv.css';
import '../../css/b/b7o2pc7la.css';
import '../../css/f/f5nmdybij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m76_9tmlz"/><path class="fi7kcnkgv"/><path class="b7o2pc7la"/><path class="f5nmdybij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pin-list-outline" /></template>
