<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9qs0v4_t.css';
import '../../css/k/kphbbgbvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p9qs0v4_t"/><path class="kphbbgbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:xprt" /></template>
