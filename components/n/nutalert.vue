<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz8cebuhr.css';
import '../../css/w/w9w5lybuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sz8cebuhr"/><path class="w9w5lybuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nutalert" /></template>
