<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq4jivysn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="eq4jivysn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:openstack-wordmark" /></template>
