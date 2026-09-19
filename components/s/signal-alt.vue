<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa5rmuqlc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="aa5rmuqlc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:signal-alt" /></template>
