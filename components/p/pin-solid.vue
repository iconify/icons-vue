<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1o8mdb_p.css';
import '../../css/t/twm3r6b7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l1o8mdb_p"/><path clip-rule="evenodd" class="twm3r6b7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:pin-solid" /></template>
