<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcgz-8zfs.css';
import '../../css/e/e7nh98xpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="tcgz-8zfs"/><path class="e7nh98xpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tumblr" /></template>
