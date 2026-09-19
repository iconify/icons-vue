<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lkhjtzb2r"/><path class="crbgp0a1u"/><path class="lu_8i1w3s"/><path class="zltivyw_w"/><path class="cbjw0gbyd"/><path class="oyln--b6t"/><path class="uzuig-jmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nora" /></template>
<style>
.cbjw0gbyd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.132 16.362a19.55 19.55 0 0 1-.21 9.814c-1.203 4.686-4.22 9.459-9.13 10.811c-2.444.786-5.147-.5-6.366-2.7c-1.312-2.209-1.897-4.982-1.354-7.504M29.405 9.109c1.53 1.706 2.64 3.72 3.34 5.878m-9.157-9.373c1.035.27 2.037.673 2.964 1.206");
}

.crbgp0a1u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.648 20.745c1.8-3.824 6.604-6.39 10.282-4.14");
}

.lkhjtzb2r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.33 14.484v-.707m0 4.685V17.06M9.289 35.412V13.506l15.043 21.906V21.437");
}

.lu_8i1w3s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.057 19.098c1.948-5.345 7.853-9.182 11.686-4.474");
}

.oyln--b6t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.233 29.778c.225-3.318-.422-6.85-2.45-9.55m-3.049 19.798c1.28-.9 2.38-2.03 3.246-3.333M21.785 42.74c1.282-.18 2.539-.51 3.744-.983m-12.284-.023c1.522.606 3.126.982 4.758 1.115m5.423-37.675c0 .923-.748 1.672-1.672 1.672h0a1.67 1.67 0 0 1-1.674-1.672v0c0-.924.748-1.674 1.672-1.674h.002c.923 0 1.672.749 1.672 1.672zm6.278 2.72c0 .924-.749 1.673-1.672 1.673h-.001a1.672 1.672 0 0 1-.001-3.346q0 0 0 0c.924 0 1.674.748 1.674 1.672zm-8.098 34.933c0 .923-.748 1.672-1.672 1.673h-.002a1.67 1.67 0 0 1-1.672-1.672v-.002a1.672 1.672 0 0 1 3.346 0zm7.322-1.725c0 .924-.747 1.673-1.671 1.674h-.002a1.67 1.67 0 0 1-1.672-1.673v0a1.672 1.672 0 0 1 3.346-.002zm6.058-10.013c0 .694-.563 1.257-1.257 1.257h0a1.257 1.257 0 0 1-1.258-1.257h0c0-.695.563-1.258 1.257-1.258h0c.695 0 1.258.563 1.258 1.258m1.388-12.325a17 17 0 0 0-.936-2.027m1.982 11.19a19.9 19.9 0 0 0-.123-5.785m-2.61 13.853a20.8 20.8 0 0 0 1.981-4.526");
}

.uzuig-jmw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.153 37.289a1.647 1.647 0 1 1-3.295-.003a1.647 1.647 0 0 1 3.295.003m3.453-16.799a1.647 1.647 0 0 1-3.293 0a1.647 1.647 0 0 1 3.293 0m.105 9.225c0 .91-.737 1.646-1.646 1.647a1.647 1.647 0 0 1 0-3.293c.91 0 1.646.737 1.647 1.646m-2.635-14.45a1.647 1.647 0 0 1-3.292 0a1.647 1.647 0 0 1 3.293 0");
}

.zltivyw_w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.229 16.038a1.646 1.646 0 1 1-3.292.08a1.646 1.646 0 0 1 3.292-.08m1.061 20.166a13 13 0 0 0 1.547-3.845m-1.045-.168c-1.728 4.07-5.938 7.203-10.461 6.905c-3.411-.046-6.6-2.316-7.63-5.6m3.815-11.086c2.913-2.844 7.918-3.557 11.213-.977c2.407 1.959 3.86 5.173 3.684 8.28");
}

</style>
