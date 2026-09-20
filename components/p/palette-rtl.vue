<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzwx4mbfz.css';
import '../../css/c/ca-_ht2ki.css';
import '../../css/q/q2m0dq3ja.css';
import '../../css/s/sdoxd1bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nzwx4mbfz"/><circle class="ca-_ht2ki"/><circle class="q2m0dq3ja"/><circle class="sdoxd1bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:palette-rtl" /></template>
