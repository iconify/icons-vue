<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdxn-ef5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="bdxn-ef5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:signal-alt-slash" /></template>
