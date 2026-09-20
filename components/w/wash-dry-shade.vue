<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf8c9wq9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf8c9wq9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:wash-dry-shade" /></template>
