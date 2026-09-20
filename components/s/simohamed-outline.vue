<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdgsixb7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xdgsixb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:simohamed-outline" /></template>
