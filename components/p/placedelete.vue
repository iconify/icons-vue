<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo3vzdbsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":770,"height":1024};
const content = `<path class="xo3vzdbsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:placedelete" /></template>
