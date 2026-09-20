<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic8i36t6o.css';
import '../../css/o/o1kf6m42c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ic8i36t6o"/><path class="o1kf6m42c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:video-16" /></template>
