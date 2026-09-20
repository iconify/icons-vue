<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmqj-lcmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nmqj-lcmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:owncloud-dark" /></template>
