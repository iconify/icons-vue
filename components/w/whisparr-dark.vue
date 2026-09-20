<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avmqk87sm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="avmqk87sm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:whisparr-dark" /></template>
