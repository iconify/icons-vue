<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0xlexmxx.css';
import '../../css/u/u3k9wcbgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u0xlexmxx"/><path class="u3k9wcbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:toodoom-dark" /></template>
