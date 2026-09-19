<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e__xz9bvx.css';
import '../../css/x/x6k9-3z8c.css';
import '../../css/s/shxaa7jyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e__xz9bvx"/><path class="x6k9-3z8c"/><path class="shxaa7jyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:tennisball" /></template>
