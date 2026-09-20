<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9zs5b_ml.css';
import '../../css/y/ymqqe9y8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9zs5b_ml"/><path class="ymqqe9y8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:sync-slash" /></template>
