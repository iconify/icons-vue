<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcupqybss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcupqybss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:scissors-off" /></template>
