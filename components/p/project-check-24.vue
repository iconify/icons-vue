<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt6oj8b5t.css';
import '../../css/z/zdpv8zbdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt6oj8b5t"/><path class="zdpv8zbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:project-check-24" /></template>
