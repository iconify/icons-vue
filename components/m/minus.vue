<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz68yo_zk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz68yo_zk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:minus" /></template>
