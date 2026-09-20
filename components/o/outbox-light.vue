<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rf4qnrbtb.css';
import '../../css/v/vdot4tock.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rf4qnrbtb"/><path class="vdot4tock"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:outbox-light" /></template>
