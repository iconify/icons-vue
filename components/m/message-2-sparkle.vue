<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0vsvnb-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0vsvnb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-2-sparkle" /></template>
