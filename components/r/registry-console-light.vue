<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd-nkug3f.css';
import '../../css/c/cqcsowpco.css';
import '../../css/e/e2doa554v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bd-nkug3f"/><path class="cqcsowpco"/><path class="e2doa554v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:registry-console-light" /></template>
