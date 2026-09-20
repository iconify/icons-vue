<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/li7fbit0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="li7fbit0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yugabytedb" /></template>
