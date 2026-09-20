<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nim_7djxm.css';
import '../../css/e/eo3ia5b9f.css';
import '../../css/o/o6c6qfb-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nim_7djxm"/><path class="eo3ia5b9f"/><path class="o6c6qfb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:registry-console-dark" /></template>
