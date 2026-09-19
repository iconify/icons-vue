<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izvz7ykmk.css';
import '../../css/j/jmjkwqnaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="izvz7ykmk"/><path class="jmjkwqnaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:nutrition" /></template>
