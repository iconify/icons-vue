<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz993v_go.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xz993v_go"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:tesla-lock" /></template>
