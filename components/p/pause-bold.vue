<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kj208xbck.css';
import '../../css/t/takxuugoc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kj208xbck"/><path class="takxuugoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pause-bold" /></template>
