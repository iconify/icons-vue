<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r057-4e-t.css';
import '../../css/w/we37umbxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="r057-4e-t"/><path class="we37umbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:semaphore-ui" /></template>
