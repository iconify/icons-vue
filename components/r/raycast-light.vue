<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8cu1gb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a8cu1gb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:raycast-light" /></template>
