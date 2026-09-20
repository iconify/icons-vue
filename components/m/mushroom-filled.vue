<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0k6b2b-n.css';
import '../../css/n/ndmpziulf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0k6b2b-n"/><path class="ndmpziulf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:mushroom-filled" /></template>
