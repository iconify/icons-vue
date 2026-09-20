<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9s-e-3im.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b9s-e-3im"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloud-forms-dark" /></template>
