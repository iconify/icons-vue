<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqqibj_vk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:potted-succulent" /></template>
<style>
.xqqibj_vk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.258 8.606q.558 3.911 3.142 5.52q-.347.225-.629.586q-.75.961-.455 2.144l.875 3.5q.473 1.893 2.425 1.894h6.768q1.952-.001 2.425-1.894l.875-3.5q.295-1.183-.455-2.144q-.282-.361-.629-.586q2.584-1.609 3.142-5.52q.011-.073.007-.147t-.022-.145t-.051-.138t-.076-.126t-.099-.108t-.119-.087t-.133-.063q-.07-.024-.143-.034q-.106-.016-.212 0q-3.104.443-5.036 2.181q.003-2.724-2.248-5.875q-.072-.102-.174-.174q-.121-.087-.267-.121q-.145-.033-.292-.009q-.147.025-.274.104t-.213.2Q9.139 7.215 9.142 9.939Q7.21 8.201 4.106 7.758q-.106-.016-.212 0q-.073.01-.143.034q-.07.025-.133.063q-.064.037-.119.087T3.4 8.05t-.076.126q-.032.066-.051.138q-.018.071-.022.145t.007.147");
}

</style>
