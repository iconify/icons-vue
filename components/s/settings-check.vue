<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn_jc1ydb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fn_jc1ydb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:settings-check" /></template>
