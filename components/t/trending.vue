<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkun__b-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkun__b-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:trending" /></template>
