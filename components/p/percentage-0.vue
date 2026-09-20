<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-eim3bku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-eim3bku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:percentage-0" /></template>
