<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecphvhbrv.css';
import '../../css/b/bzxzk3bln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ecphvhbrv"/><path class="bzxzk3bln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sonatype-nexus-repository" /></template>
