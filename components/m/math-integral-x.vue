<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsag7tpli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsag7tpli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:math-integral-x" /></template>
