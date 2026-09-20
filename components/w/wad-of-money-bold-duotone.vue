<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5lttmq7g.css';
import '../../css/n/n6jo5gq3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5lttmq7g"/><path class="n6jo5gq3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wad-of-money-bold-duotone" /></template>
