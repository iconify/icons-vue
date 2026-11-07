<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gce_q8bwk.css';
import '../../css/p/pahtwyu4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gce_q8bwk"/><path class="pahtwyu4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:settings-bold-duotone" /></template>
