<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8vnt_j9i.css';
import '../../css/p/pxdv6ta5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8vnt_j9i"/><path class="pxdv6ta5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mirror-2-bold-duotone" /></template>
