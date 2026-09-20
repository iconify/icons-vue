<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szqeyhbqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="szqeyhbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:osticket-light" /></template>
