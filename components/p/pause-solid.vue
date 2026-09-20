<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea7vas5oa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea7vas5oa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:pause-solid" /></template>
