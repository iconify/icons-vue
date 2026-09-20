<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykwimr7ks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykwimr7ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:test-tube" /></template>
