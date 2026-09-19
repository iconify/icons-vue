<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh1j0mb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gh1j0mb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pointing-right-02" /></template>
