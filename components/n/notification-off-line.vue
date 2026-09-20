<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjayss3jf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjayss3jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:notification-off-line" /></template>
