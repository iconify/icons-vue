<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljdfx9b4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ljdfx9b4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-office-document-light" /></template>
