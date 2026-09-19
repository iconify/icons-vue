<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puaxb3bpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="puaxb3bpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:riot-old" /></template>
