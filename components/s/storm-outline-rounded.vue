<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wj3pppb-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:storm-outline-rounded" /></template>
<style>
.wj3pppb-l {
  fill: currentColor;
  d: path("M18.45 21.116q-.202 0-.299-.191q-.097-.19-.03-.437q.483-1.574.614-3.194q.13-1.619-.085-3.244q-.61 2.229-2.46 3.59Q14.338 19 12 19q-1.85 0-3.3-.92t-2.448-2.426t-1.514-3.46t-.515-4.006q0-1.203.147-2.38q.147-1.175.478-2.33q.067-.262.25-.428t.452-.165q.202 0 .299.19t.03.437q-.458 1.575-.601 3.194T5.35 9.95q.61-2.229 2.46-3.59Q9.663 5 12 5q1.85 0 3.3.92t2.448 2.426t1.514 3.451t.515 4.015q0 1.204-.147 2.38t-.478 2.33q-.067.263-.25.428q-.183.166-.452.166M12 18q2.5 0 4.25-1.75T18 12t-1.75-4.25T12 6T7.75 7.75T6 12t1.75 4.25T12 18m2.123-3.877Q15 13.246 15 12t-.877-2.123T12 9t-2.123.877T9 12t.877 2.123T12 15t2.123-.877m-3.535-.71Q10 12.825 10 12t.588-1.412T12 10t1.413.588T14 12t-.587 1.413T12 14t-1.412-.587M12 12");
}

</style>
