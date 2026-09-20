<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4kggwbad.css';
import '../../css/u/uek9cd0sz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="n4kggwbad"/><path clip-rule="evenodd" class="uek9cd0sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:pagination-alt-solid" /></template>
