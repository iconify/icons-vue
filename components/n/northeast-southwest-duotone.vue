<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfndtr6jn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfndtr6jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:northeast-southwest-duotone" /></template>
