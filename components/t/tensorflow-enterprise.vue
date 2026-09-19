<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjnlq7v4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjnlq7v4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:tensorflow-enterprise" /></template>
