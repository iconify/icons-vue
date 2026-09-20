<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la7hr5__c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="la7hr5__c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:old-navy-light" /></template>
