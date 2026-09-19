<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqie4kb4q.css';
import '../../css/i/ifa7j6beo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqie4kb4q"/><path class="ifa7j6beo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:package-upgrade" /></template>
