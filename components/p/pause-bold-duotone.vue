<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kj208xbck.css';
import '../../css/g/gz18a5efe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kj208xbck"/><path class="gz18a5efe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pause-bold-duotone" /></template>
