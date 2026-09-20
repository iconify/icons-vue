<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vunaabcms.css';
import '../../css/o/om-jm0bjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vunaabcms"/><path clip-rule="evenodd" class="om-jm0bjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:usn" /></template>
