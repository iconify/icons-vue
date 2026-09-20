<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzsnjchuv.css';
import '../../css/a/a_b-kq5rh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzsnjchuv"/><path class="a_b-kq5rh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:music-rectangle-add-filled" /></template>
