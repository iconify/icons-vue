<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwf0qho5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwf0qho5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:message-solid" /></template>
