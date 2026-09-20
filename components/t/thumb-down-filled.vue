<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh3y82bpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vh3y82bpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:thumb-down-filled" /></template>
