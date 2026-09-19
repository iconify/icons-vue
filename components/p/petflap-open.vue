<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j125o4bqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j125o4bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:petflap-open" /></template>
