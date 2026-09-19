<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b04q-pbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1023};
const content = `<path class="b04q-pbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:split" /></template>
