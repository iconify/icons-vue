<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqv7gzxhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqv7gzxhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sydney-metro" /></template>
