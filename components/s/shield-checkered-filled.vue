<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zka7-zb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zka7-zb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:shield-checkered-filled" /></template>
