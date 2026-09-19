<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj36n2brk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oj36n2brk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pin-02" /></template>
