<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8j2874re.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8j2874re"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:point-right-solid" /></template>
