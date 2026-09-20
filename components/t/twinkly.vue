<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b833w1u7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b833w1u7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:twinkly" /></template>
