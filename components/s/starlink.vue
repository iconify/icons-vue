<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqwkt9bhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqwkt9bhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:starlink" /></template>
