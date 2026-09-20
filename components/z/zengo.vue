<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmb706_bp.css';
import '../../css/j/j3ziv3b8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmb706_bp"/><path class="j3ziv3b8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:zengo" /></template>
