<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqpwqvbjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rqpwqvbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:target-16-solid" /></template>
