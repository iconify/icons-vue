<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw82srpqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pw82srpqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:valkey-light" /></template>
