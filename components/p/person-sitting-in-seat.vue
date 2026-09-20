<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw4e8vbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cw4e8vbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-sitting-in-seat" /></template>
