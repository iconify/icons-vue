<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edf2mabxb.css';
import '../../css/w/wqggdqb6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edf2mabxb"/><path class="wqggdqb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:unread-bold-duotone" /></template>
