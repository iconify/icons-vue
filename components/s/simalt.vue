<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udhv20bpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1025};
const content = `<path class="udhv20bpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:simalt" /></template>
