<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl3q62b8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fl3q62b8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:pager" /></template>
