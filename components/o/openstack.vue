<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opfh_kb8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opfh_kb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:openstack" /></template>
