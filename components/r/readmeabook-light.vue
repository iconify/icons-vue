<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/saj1_ob7a.css';
import '../../css/b/bzm068cfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="saj1_ob7a"/><path class="bzm068cfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:readmeabook-light" /></template>
