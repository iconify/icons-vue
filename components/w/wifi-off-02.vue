<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nunwyac9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nunwyac9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:wifi-off-02" /></template>
