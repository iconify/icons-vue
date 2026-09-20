<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_9emp3jk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l_9emp3jk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:twitchrise" /></template>
