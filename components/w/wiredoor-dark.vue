<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1se23bda.css';
import '../../css/e/ep8yvx7kc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g1se23bda"/><path class="ep8yvx7kc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wiredoor-dark" /></template>
