<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8lc7zb3l.css';
import '../../css/n/nc55f-bpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8lc7zb3l"/><path clip-rule="evenodd" class="nc55f-bpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:minus-circle-24" /></template>
