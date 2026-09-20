<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uid5ybegl.css';
import '../../css/f/fokopnbqa.css';
import '../../css/g/gqyaulbpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uid5ybegl"/><path class="fokopnbqa"/><path class="gqyaulbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-powerpoint-light" /></template>
