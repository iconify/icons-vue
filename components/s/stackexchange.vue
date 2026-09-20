<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_q-1whlo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_q-1whlo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:stackexchange" /></template>
