<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obhljr3lk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="obhljr3lk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:thumbtack-slash" /></template>
