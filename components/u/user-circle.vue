<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cm_28obyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:user-circle" /></template>
<style>
.cm_28obyk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m7.245-5.505Q7.75 7.74 7.75 9.5t1.245 3.005T12 13.75t3.005-1.245T16.25 9.5t-1.245-3.005T12 5.25T8.995 6.495M12 14.75q-4.168 0-6.604 3.305q-.088.12-.124.265t-.014.292q.023.148.1.276q.077.127.197.216q.06.044.126.075q.067.031.139.049t.146.021q.073.004.146-.007q.073-.012.143-.037t.133-.063t.117-.088q.055-.05.099-.109Q8.59 16.25 12 16.25t5.396 2.695q.044.059.099.109q.054.05.117.088q.064.038.133.063q.07.025.143.037t.146.007q.074-.003.146-.021t.139-.049q.066-.031.126-.075q.059-.044.109-.099q.05-.054.088-.117q.038-.064.063-.133q.025-.07.037-.143t.007-.146q-.003-.074-.021-.146t-.049-.139q-.031-.066-.075-.126Q16.168 14.75 12 14.75");
}

</style>
