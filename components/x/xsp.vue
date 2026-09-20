<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gafgfqgjb.css';
import '../../css/l/lnil9jecv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gafgfqgjb"/><path class="lnil9jecv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:xsp" /></template>
