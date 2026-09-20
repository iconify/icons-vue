<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pte5rzrpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pte5rzrpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mastodon-dark" /></template>
