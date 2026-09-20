<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-dk98buy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b-dk98buy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opensuse-evergreen" /></template>
