<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odw3a5f3a.css';
import '../../css/l/l8u2h9byi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odw3a5f3a"/><path class="l8u2h9byi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:mobile-list-filled" /></template>
