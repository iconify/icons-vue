<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz2dtsbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yz2dtsbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openldap-dark" /></template>
