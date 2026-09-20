<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfrm-9bie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfrm-9bie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:x-filled" /></template>
