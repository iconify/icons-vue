<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_kk64s-x.css';
import '../../css/p/p_p4lxbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x_kk64s-x"/><path class="p_p4lxbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:spotify-for-creators" /></template>
