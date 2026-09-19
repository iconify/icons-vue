<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7-kc7-jx.css';
import '../../css/b/b6u0ge0rs.css';
import '../../css/t/tb4g6uqca.css';
import '../../css/n/n4dsx_bie.css';
import '../../css/n/n3al-6ncs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7-kc7-jx"/><path class="b6u0ge0rs"/><rect class="tb4g6uqca"/><path class="n4dsx_bie"/><rect class="n3al-6ncs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:partner-interconnect" /></template>
