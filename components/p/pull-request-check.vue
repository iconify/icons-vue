<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9t6xzb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9t6xzb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:pull-request-check" /></template>
