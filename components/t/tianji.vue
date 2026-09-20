<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a11tzybnd.css';
import '../../css/a/ao20o-byk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a11tzybnd"/><path class="ao20o-byk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tianji" /></template>
