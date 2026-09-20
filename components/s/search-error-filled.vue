<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtdsctbtj.css';
import '../../css/w/w6qwevbda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtdsctbtj"/><path class="w6qwevbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:search-error-filled" /></template>
