<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh7f1hoyt.css';
import '../../css/m/mmgfxwbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bh7f1hoyt"/><path clip-rule="evenodd" class="mmgfxwbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:zip-solid" /></template>
