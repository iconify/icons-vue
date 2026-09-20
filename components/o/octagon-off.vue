<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opit56l-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opit56l-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:octagon-off" /></template>
