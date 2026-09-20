<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0bs2o6zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0bs2o6zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-letter-r-filled" /></template>
