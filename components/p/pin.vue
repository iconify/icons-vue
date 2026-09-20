<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9-dmt_9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9-dmt_9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:pin" /></template>
