<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb4b0hbgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lb4b0hbgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:raft-with-circle" /></template>
